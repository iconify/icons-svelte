<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m799961bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m799961bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:more-vertical-20" {...props}></Icon>
