<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hobd9v3ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hobd9v3ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-invoice" {...props}></Icon>
