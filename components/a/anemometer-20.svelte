<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd98t6bsy.css';
import '../../css/n/n6krgwbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nd98t6bsy"/><path class="n6krgwbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anemometer-20" {...props}></Icon>
