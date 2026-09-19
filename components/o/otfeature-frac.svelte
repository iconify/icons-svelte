<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acdt3wbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="acdt3wbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-frac" {...props}></Icon>
