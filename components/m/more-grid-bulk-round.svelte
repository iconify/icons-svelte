<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_m8swbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_m8swbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:more-grid-bulk-round" {...props}></Icon>
