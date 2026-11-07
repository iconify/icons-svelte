<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl1y521md.css';
import '../../css/l/lqz0ivbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zl1y521md"/><path class="lqz0ivbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-down-bold-duotone" {...props}></Icon>
