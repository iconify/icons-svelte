<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8u2_nrqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="k8u2_nrqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:guidenai" {...props}></Icon>
