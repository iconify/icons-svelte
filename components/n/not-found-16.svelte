<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcb8zfcla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gcb8zfcla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:not-found-16" {...props}></Icon>
