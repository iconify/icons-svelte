<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hli0nqqef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hli0nqqef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fish-filled" {...props}></Icon>
