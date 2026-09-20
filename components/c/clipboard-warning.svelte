<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4kdn_aes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4kdn_aes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-warning" {...props}></Icon>
