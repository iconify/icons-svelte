<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gstxg1kyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gstxg1kyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:battery-half" {...props}></Icon>
