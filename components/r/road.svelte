<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub_fq4b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ub_fq4b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:road" {...props}></Icon>
