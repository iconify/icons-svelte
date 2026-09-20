<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe3x9j2kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe3x9j2kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alipay-line" {...props}></Icon>
