<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0_xy5__y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0_xy5__y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-weibo" {...props}></Icon>
