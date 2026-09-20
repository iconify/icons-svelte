<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtv447bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jtv447bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:calendar-plus-outline" {...props}></Icon>
