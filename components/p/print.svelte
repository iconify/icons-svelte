<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv5412blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":683};
const content = `<path class="gv5412blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:print" {...props}></Icon>
