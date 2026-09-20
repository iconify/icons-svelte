<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khf3n-v7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khf3n-v7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-asana" {...props}></Icon>
