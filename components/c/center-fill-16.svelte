<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqrqcmb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nqrqcmb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:center-fill-16" {...props}></Icon>
