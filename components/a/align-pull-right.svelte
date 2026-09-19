<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo1dt-bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oo1dt-bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:align-pull-right" {...props}></Icon>
