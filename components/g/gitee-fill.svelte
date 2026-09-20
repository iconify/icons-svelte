<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7s_qxalq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7s_qxalq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gitee-fill" {...props}></Icon>
