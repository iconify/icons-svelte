<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct4q6eb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ct4q6eb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:direction-outline" {...props}></Icon>
