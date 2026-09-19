<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr1lh7bho.css';
import '../../css/y/yp-o87trv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr1lh7bho"/><path class="yp-o87trv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:copy-plus" {...props}></Icon>
