<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou9mpkptl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ou9mpkptl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:content-navigator-edit-service-download" {...props}></Icon>
