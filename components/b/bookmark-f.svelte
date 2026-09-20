<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6g11fwan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="e6g11fwan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:bookmark-f" {...props}></Icon>
