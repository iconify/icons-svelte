<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3qemvell.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3qemvell"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-wireless" {...props}></Icon>
