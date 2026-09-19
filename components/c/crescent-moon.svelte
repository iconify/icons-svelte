<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sin0hb8ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sin0hb8ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:crescent-moon" {...props}></Icon>
