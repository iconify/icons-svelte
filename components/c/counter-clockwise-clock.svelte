<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulc_957tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ulc_957tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:counter-clockwise-clock" {...props}></Icon>
