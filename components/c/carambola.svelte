<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4tuu_d8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4tuu_d8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:carambola" {...props}></Icon>
