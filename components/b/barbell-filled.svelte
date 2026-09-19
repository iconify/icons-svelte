<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on5k_mb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on5k_mb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:barbell-filled" {...props}></Icon>
