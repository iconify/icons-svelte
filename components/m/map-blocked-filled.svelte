<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlfrtxgac.css';
import '../../css/v/vkk5k5byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlfrtxgac"/><path class="vkk5k5byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-blocked-filled" {...props}></Icon>
