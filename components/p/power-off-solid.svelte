<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9mvx7bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z9mvx7bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:power-off-solid" {...props}></Icon>
