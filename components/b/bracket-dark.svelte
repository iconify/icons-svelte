<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbb582b_y.css';
import '../../css/o/onr57qb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fbb582b_y"/><path class="onr57qb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bracket-dark" {...props}></Icon>
