<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no18gackv.css';
import '../../css/e/e9f-1ebjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="no18gackv"/><path class="e9f-1ebjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cube-outline" {...props}></Icon>
