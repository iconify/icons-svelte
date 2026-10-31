<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnjtahbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnjtahbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:droplet-round" {...props}></Icon>
