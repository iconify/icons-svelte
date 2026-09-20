<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnze186_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnze186_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:ai-solid" {...props}></Icon>
