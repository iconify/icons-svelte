<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z183d_i5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z183d_i5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-off-bold" {...props}></Icon>
