<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5lq4rg2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="k5lq4rg2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:reddit" {...props}></Icon>
