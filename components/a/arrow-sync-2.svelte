<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq48p7xon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq48p7xon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-sync-2" {...props}></Icon>
