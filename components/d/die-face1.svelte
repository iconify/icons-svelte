<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyiugab0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dyiugab0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face1" {...props}></Icon>
