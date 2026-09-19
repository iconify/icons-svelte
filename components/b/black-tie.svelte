<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yijhkhrdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yijhkhrdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:black-tie" {...props}></Icon>
