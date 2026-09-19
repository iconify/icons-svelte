<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt8n9obpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="wt8n9obpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:account-add" {...props}></Icon>
