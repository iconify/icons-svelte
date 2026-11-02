<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl6wa7bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl6wa7bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lock-open-line" {...props}></Icon>
