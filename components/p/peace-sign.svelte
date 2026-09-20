<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/milj044hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="milj044hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:peace-sign" {...props}></Icon>
