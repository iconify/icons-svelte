<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz9rk9b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":481,"height":512};
const content = `<path class="tz9rk9b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openexr" {...props}></Icon>
