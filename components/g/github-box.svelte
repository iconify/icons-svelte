<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvdt7r95i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="hvdt7r95i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:github-box" {...props}></Icon>
