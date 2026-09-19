<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u97tclbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="u97tclbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:gift" {...props}></Icon>
