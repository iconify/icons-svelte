<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vya01ab-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vya01ab-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deploy-rules" {...props}></Icon>
