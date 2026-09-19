<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut__hv4nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ut__hv4nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:pandora" {...props}></Icon>
