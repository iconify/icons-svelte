<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1g175bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m1g175bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-number-rtl-fill-16" {...props}></Icon>
