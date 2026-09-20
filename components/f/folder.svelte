<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e09-accts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e09-accts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:folder" {...props}></Icon>
