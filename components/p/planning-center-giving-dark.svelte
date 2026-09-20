<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb18fn7er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mb18fn7er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-giving-dark" {...props}></Icon>
