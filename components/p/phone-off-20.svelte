<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe9koubop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oe9koubop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-off-20" {...props}></Icon>
