<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsl067b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsl067b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-top-open-fill" {...props}></Icon>
