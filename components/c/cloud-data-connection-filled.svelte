<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyki04bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyki04bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-data-connection-filled" {...props}></Icon>
