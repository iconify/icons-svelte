<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_3eqdman.css';
import '../../css/e/eh1h-1bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_3eqdman"/><path class="eh1h-1bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-paste" {...props}></Icon>
