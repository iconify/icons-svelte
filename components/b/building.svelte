<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkp8n4jck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkp8n4jck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:building" {...props}></Icon>
