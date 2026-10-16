<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozbstuboh.css';
import '../../css/u/u3e4gfbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ozbstuboh"/><path class="u3e4gfbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-missed-20-bold" {...props}></Icon>
