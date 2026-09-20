<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h940q7b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h940q7b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-specialty-knee-1-bold" {...props}></Icon>
