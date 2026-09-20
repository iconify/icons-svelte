<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5489ibkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b5489ibkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pawprint-with-greek-cross" {...props}></Icon>
