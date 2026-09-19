<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds-s1ulgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ds-s1ulgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:center-stroke-12" {...props}></Icon>
