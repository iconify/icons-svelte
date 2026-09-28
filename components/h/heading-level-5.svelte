<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfrr6dbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="rfrr6dbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:heading-level-5" {...props}></Icon>
