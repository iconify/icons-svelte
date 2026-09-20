<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dak5-acry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dak5-acry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:redo-alt" {...props}></Icon>
