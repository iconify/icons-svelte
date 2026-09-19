<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olh7nccxm.css';
import '../../css/m/m0esjaiqj.css';
import '../../css/j/jhkw66bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="olh7nccxm"/><rect class="m0esjaiqj"/><path class="jhkw66bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-horizontal-justify-end-filled" {...props}></Icon>
