<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaodrq99u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oaodrq99u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:aerialway-15" {...props}></Icon>
