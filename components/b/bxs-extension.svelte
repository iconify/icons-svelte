<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e521f7caz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e521f7caz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-extension" {...props}></Icon>
