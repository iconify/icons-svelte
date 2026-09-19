<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztsv9wbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="ztsv9wbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:deskpro" {...props}></Icon>
