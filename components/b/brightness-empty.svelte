<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll2_3eb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll2_3eb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:brightness-empty" {...props}></Icon>
