<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqfj8n7ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqfj8n7ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drag" {...props}></Icon>
