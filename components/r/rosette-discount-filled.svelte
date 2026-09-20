<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r45pi6b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r45pi6b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rosette-discount-filled" {...props}></Icon>
