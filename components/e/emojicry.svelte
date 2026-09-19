<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua2y-eb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ua2y-eb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emojicry" {...props}></Icon>
