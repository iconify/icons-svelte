<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqx7c2hlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqx7c2hlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:google-round" {...props}></Icon>
