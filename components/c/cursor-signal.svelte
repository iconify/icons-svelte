<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4mgtmfcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4mgtmfcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-signal" {...props}></Icon>
