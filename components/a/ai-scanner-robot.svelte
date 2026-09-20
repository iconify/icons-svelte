<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en8xd5bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="en8xd5bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ai-scanner-robot" {...props}></Icon>
