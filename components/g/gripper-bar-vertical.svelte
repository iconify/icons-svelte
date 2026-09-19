<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq4fs4big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bq4fs4big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:gripper-bar-vertical" {...props}></Icon>
