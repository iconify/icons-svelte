<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjc7l4brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tjc7l4brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:report-general" {...props}></Icon>
