<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-tqbb_cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-tqbb_cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:moon" {...props}></Icon>
