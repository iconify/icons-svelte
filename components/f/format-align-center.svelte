<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpje716il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="vpje716il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-align-center" {...props}></Icon>
