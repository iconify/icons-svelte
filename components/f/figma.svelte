<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9uy5-hfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c9uy5-hfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:figma" {...props}></Icon>
