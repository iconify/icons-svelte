<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip6956biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ip6956biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-compare-solid" {...props}></Icon>
