<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6xeln-ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c6xeln-ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bluetooth-connected-20" {...props}></Icon>
