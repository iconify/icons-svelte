<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwxv6dbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwxv6dbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-drizzle" {...props}></Icon>
