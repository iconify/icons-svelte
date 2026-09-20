<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm1ygvb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm1ygvb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:carousel-horizontal" {...props}></Icon>
