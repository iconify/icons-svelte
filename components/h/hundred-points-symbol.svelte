<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah82h4wex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ah82h4wex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hundred-points-symbol" {...props}></Icon>
