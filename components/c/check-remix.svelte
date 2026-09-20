<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzjavk1ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mzjavk1ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:check-remix" {...props}></Icon>
