<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll4-n--4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ll4-n--4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:eye-off" {...props}></Icon>
