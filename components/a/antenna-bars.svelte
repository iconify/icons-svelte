<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x838nnz9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x838nnz9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:antenna-bars" {...props}></Icon>
