<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk8uo8bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dk8uo8bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:n8n" {...props}></Icon>
