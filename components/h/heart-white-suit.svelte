<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/latsbryka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="latsbryka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:heart-white-suit" {...props}></Icon>
