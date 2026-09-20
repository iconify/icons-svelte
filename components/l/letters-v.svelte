<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8wnmp3xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8wnmp3xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-v" {...props}></Icon>
