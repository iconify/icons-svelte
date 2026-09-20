<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu2b2g8_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu2b2g8_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:command" {...props}></Icon>
