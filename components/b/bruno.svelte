<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgqejvb_u.css';
import '../../css/j/jcx6hxbdf.css';
import '../../css/x/xrbve6iev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cgqejvb_u"/><path class="jcx6hxbdf"/><path class="xrbve6iev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:bruno" {...props}></Icon>
