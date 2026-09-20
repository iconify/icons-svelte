<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxbf69ndo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rxbf69ndo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:mug" {...props}></Icon>
