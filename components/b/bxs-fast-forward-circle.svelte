<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4503eb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4503eb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-fast-forward-circle" {...props}></Icon>
