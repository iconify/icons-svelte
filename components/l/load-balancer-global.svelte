<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_s_snbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ae_s_snbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:load-balancer-global" {...props}></Icon>
