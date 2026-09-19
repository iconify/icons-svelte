<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvpbq8bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="hvpbq8bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:print" {...props}></Icon>
