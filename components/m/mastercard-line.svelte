<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjhk_eb_p.css';
import '../../css/k/k5xt08bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjhk_eb_p"/><path class="k5xt08bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mastercard-line" {...props}></Icon>
