<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yox9j2bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="yox9j2bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:entrance-alt1-11" {...props}></Icon>
