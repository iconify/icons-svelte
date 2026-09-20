<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbup9w5tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbup9w5tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-list-bulleted-triangle" {...props}></Icon>
