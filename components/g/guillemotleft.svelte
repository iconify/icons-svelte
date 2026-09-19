<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuiynvcqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":516,"height":614};
const content = `<path class="kuiynvcqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:guillemotleft" {...props}></Icon>
