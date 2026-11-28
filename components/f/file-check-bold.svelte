<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi287vbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fi287vbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-check-bold" {...props}></Icon>
