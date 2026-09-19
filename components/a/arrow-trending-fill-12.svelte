<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp2abxbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sp2abxbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-trending-fill-12" {...props}></Icon>
