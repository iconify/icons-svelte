<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vek2j8b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1185,"height":1000};
const content = `<path class="vek2j8b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:forward" {...props}></Icon>
