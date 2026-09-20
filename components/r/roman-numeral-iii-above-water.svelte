<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr4z8rb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gr4z8rb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-iii-above-water" {...props}></Icon>
