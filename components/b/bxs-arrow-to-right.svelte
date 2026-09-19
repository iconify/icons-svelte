<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf_28cc7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf_28cc7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-arrow-to-right" {...props}></Icon>
