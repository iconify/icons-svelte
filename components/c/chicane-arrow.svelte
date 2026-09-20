<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caizf_bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="caizf_bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:chicane-arrow" {...props}></Icon>
