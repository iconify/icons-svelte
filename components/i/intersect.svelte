<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bab7g1bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bab7g1bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:intersect" {...props}></Icon>
