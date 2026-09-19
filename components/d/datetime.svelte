<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0s51ebnl.css';
import '../../css/p/pzvbzhw1c.css';
import '../../css/z/z-_-ey0ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z0s51ebnl"/><path class="pzvbzhw1c"/><path class="z-_-ey0ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:datetime" {...props}></Icon>
