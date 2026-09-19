<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7_lms_6w.css';
import '../../css/v/vbpiltbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="t7_lms_6w"/><path class="vbpiltbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gallery-horizontal-end-filled" {...props}></Icon>
