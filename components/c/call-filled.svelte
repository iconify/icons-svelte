<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxl0p-bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxl0p-bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:call-filled" {...props}></Icon>
