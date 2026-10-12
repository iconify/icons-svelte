<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4i-4cr0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4i-4cr0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:puzzle-filled" {...props}></Icon>
