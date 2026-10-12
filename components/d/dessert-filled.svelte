<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs-mtrbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rs-mtrbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dessert-filled" {...props}></Icon>
