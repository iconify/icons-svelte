<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz5hput7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5hput7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heart-plus" {...props}></Icon>
