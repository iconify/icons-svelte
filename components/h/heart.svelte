<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1y8vagqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u1y8vagqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:heart" {...props}></Icon>
