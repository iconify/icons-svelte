<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow_orow8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ow_orow8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-chapel" {...props}></Icon>
