<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rewug1ppt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rewug1ppt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-drizzle-48" {...props}></Icon>
