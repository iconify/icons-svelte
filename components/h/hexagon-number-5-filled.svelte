<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6f9kcbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6f9kcbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-number-5-filled" {...props}></Icon>
