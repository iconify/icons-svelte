<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9mjsubkx.css';
import '../../css/q/qaip3db6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g9mjsubkx"/><path class="qaip3db6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bus-48-bold" {...props}></Icon>
