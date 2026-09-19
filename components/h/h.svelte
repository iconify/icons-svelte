<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eigvuhbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="eigvuhbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:h" {...props}></Icon>
