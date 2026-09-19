<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8n63d11k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f8n63d11k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:logo-windows" {...props}></Icon>
