<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc3w86psn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc3w86psn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rotate-cw-solid" {...props}></Icon>
