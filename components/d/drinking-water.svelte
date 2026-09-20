<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk08j9bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sk08j9bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:drinking-water" {...props}></Icon>
