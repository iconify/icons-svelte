<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwg97objp.css';
import '../../css/h/hxjbwwbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwg97objp"/><path class="hxjbwwbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-amazon-outline" {...props}></Icon>
