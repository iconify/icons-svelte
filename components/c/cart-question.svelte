<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_k_-s3dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_k_-s3dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cart-question" {...props}></Icon>
