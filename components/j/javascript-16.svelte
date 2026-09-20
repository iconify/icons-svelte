<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyvjpm-mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gyvjpm-mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:javascript-16" {...props}></Icon>
