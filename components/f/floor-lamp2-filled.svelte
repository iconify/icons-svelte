<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhiy3obdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhiy3obdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:floor-lamp2-filled" {...props}></Icon>
