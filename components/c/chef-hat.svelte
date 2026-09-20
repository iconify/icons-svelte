<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_w07d5xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="k_w07d5xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chef-hat" {...props}></Icon>
