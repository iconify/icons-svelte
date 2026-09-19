<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr_by2_hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr_by2_hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-search" {...props}></Icon>
