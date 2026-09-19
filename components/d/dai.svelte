<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo-zpgbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oo-zpgbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dai" {...props}></Icon>
