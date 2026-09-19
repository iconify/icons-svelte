<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_kpmub2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k_kpmub2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-in-fill-16" {...props}></Icon>
