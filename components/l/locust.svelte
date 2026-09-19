<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh2z3we9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="vh2z3we9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:locust" {...props}></Icon>
