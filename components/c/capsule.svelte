<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t635e0gnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="t635e0gnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:capsule" {...props}></Icon>
