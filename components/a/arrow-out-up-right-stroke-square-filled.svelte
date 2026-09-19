<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrw7eflsk.css';
import '../../css/i/isu2qlb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw7eflsk"/><path class="isu2qlb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-right-stroke-square-filled" {...props}></Icon>
