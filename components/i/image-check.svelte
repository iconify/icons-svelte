<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si-995bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si-995bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-check" {...props}></Icon>
