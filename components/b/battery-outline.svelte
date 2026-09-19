<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxb9-f_tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxb9-f_tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:battery-outline" {...props}></Icon>
