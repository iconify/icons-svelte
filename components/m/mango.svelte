<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc7ct3nlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hc7ct3nlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:mango" {...props}></Icon>
