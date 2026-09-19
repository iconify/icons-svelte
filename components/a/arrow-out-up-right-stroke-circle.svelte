<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrw7eflsk.css';
import '../../css/x/xxyrztbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw7eflsk"/><path class="xxyrztbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-right-stroke-circle" {...props}></Icon>
