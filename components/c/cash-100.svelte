<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owf8r9b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owf8r9b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-100" {...props}></Icon>
