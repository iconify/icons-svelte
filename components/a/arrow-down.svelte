<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mooostb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mooostb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-down" {...props}></Icon>
