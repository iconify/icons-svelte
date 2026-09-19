<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao-gebb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ao-gebb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pistol" {...props}></Icon>
