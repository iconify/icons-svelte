<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftlaln56r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ftlaln56r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:compsition-horizontal-flat" {...props}></Icon>
