<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jumt7_b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":242,"height":512};
const content = `<path class="jumt7_b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pawn" {...props}></Icon>
