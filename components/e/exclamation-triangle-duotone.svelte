<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl1padfwm.css';
import '../../css/j/j2w1i02yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl1padfwm"/><path class="j2w1i02yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-triangle-duotone" {...props}></Icon>
