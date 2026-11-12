<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6dpq6bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6dpq6bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flatnotes-dark" {...props}></Icon>
