<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm0lb9bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qm0lb9bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:new-message" {...props}></Icon>
