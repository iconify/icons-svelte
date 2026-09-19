<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnm2yubav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nnm2yubav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:history-fill-16" {...props}></Icon>
