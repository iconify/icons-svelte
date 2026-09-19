<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3o99tboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x3o99tboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:gear" {...props}></Icon>
