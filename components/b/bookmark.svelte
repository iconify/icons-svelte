<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aihtfcq2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="aihtfcq2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bookmark" {...props}></Icon>
