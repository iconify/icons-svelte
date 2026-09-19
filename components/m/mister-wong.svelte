<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k05qhhbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":488};
const content = `<path class="k05qhhbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:mister-wong" {...props}></Icon>
