<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv23j4gpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gv23j4gpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bus" {...props}></Icon>
