<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukc5chhna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukc5chhna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-spill-20-bold" {...props}></Icon>
