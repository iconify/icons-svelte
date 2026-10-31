<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kllp8i1cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kllp8i1cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-minus-fill-round" {...props}></Icon>
