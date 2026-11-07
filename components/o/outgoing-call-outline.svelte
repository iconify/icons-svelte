<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtoomg9sp.css';
import '../../css/a/accmcc7bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xtoomg9sp"/><path class="accmcc7bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:outgoing-call-outline" {...props}></Icon>
