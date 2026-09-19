<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln7ya2bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln7ya2bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chevron-right-square-filled" {...props}></Icon>
