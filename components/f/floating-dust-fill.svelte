<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn7lzrvnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vn7lzrvnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:floating-dust-fill" {...props}></Icon>
