<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/han3ucbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="han3ucbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:accept-circle" {...props}></Icon>
