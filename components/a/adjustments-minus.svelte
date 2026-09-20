<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7e5-73sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7e5-73sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-minus" {...props}></Icon>
