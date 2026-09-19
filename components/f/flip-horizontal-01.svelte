<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uev9vcctv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uev9vcctv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flip-horizontal-01" {...props}></Icon>
