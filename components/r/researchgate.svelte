<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq-x_vb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="aq-x_vb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:researchgate" {...props}></Icon>
