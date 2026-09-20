<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf5jombhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nf5jombhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:arrow-down-right-16" {...props}></Icon>
