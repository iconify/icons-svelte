<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncmsvebhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ncmsvebhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:globe-europe-africa-fill" {...props}></Icon>
