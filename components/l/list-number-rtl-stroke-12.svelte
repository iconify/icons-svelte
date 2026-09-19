<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6butdbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o6butdbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-number-rtl-stroke-12" {...props}></Icon>
