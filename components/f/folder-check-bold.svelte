<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h55a4xb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h55a4xb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:folder-check-bold" {...props}></Icon>
