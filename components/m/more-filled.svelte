<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t09xm3etv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t09xm3etv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:more-filled" {...props}></Icon>
