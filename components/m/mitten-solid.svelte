<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aryst_pgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aryst_pgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mitten-solid" {...props}></Icon>
