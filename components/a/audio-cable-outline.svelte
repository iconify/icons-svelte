<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lleusabbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lleusabbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:audio-cable-outline" {...props}></Icon>
