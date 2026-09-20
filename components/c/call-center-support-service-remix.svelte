<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcmcroazx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jcmcroazx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:call-center-support-service-remix" {...props}></Icon>
