<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4jo3rb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d4jo3rb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gba-outline" {...props}></Icon>
