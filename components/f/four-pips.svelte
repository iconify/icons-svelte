<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmgb4967r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pmgb4967r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:four-pips" {...props}></Icon>
