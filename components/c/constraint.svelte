<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7c-sfo1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7c-sfo1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:constraint" {...props}></Icon>
