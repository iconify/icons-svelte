<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdq5wv8mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gdq5wv8mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:btg" {...props}></Icon>
