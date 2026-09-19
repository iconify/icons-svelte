<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_6xd8_wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":384};
const content = `<path class="e_6xd8_wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airline-seat-legroom-reduced" {...props}></Icon>
