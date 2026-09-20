<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x67dcf5cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x67dcf5cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:archery-arrow" {...props}></Icon>
