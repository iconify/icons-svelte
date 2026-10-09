<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lik4byo7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lik4byo7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:component-20-bold" {...props}></Icon>
