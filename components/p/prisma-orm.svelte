<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxfw2ll-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxfw2ll-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:prisma-orm" {...props}></Icon>
