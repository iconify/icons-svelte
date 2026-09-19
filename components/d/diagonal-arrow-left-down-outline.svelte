<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d61kb7bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d61kb7bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:diagonal-arrow-left-down-outline" {...props}></Icon>
