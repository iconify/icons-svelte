<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr89lux6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kr89lux6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:norg" {...props}></Icon>
