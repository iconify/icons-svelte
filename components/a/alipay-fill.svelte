<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqf-js7hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqf-js7hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alipay-fill" {...props}></Icon>
