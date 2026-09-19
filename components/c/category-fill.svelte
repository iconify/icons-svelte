<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhvq4ybnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhvq4ybnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:category-fill" {...props}></Icon>
