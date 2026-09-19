<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vat3ri6pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vat3ri6pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:note-sticky" {...props}></Icon>
