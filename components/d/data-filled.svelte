<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2jkeg0tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="p2jkeg0tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:data-filled" {...props}></Icon>
