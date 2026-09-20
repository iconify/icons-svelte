<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbnll0bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbnll0bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lock-star" {...props}></Icon>
