<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq8kg371w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq8kg371w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fold-up" {...props}></Icon>
