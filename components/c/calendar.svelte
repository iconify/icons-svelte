<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omt14xb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="omt14xb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:calendar" {...props}></Icon>
