<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snv3cbbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="snv3cbbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:exclamation-diamond-fill" {...props}></Icon>
