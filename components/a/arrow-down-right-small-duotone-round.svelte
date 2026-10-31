<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvv_3bcke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvv_3bcke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-right-small-duotone-round" {...props}></Icon>
