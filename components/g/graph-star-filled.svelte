<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7urrmbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7urrmbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:graph-star-filled" {...props}></Icon>
