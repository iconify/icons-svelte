<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pssxu37lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pssxu37lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box" {...props}></Icon>
