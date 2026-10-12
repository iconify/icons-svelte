<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s34wg9bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s34wg9bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pentagon-filled" {...props}></Icon>
