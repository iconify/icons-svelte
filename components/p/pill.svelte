<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzno8663c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gzno8663c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pill" {...props}></Icon>
