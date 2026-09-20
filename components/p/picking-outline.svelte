<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oizeq86kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oizeq86kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picking-outline" {...props}></Icon>
