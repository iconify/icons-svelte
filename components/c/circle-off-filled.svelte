<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oboucfolx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oboucfolx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-off-filled" {...props}></Icon>
