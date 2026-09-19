<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8e9ji_ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="k8e9ji_ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-peace" {...props}></Icon>
