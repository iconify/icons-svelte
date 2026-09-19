<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toaz7g1ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="toaz7g1ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:currency-yen" {...props}></Icon>
