<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-a3n1cad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":960};
const content = `<path class="z-a3n1cad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dominoeight" {...props}></Icon>
