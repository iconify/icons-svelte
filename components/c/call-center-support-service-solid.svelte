<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzes-1bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nzes-1bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:call-center-support-service-solid" {...props}></Icon>
