<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca5_jfd3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":520};
const content = `<path class="ca5_jfd3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:resize" {...props}></Icon>
