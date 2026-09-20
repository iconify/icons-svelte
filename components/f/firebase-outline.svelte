<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx8h4crue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vx8h4crue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:firebase-outline" {...props}></Icon>
