<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcvnlhb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcvnlhb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading" {...props}></Icon>
