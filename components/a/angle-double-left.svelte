<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mro34mbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":992,"height":1280};
const content = `<path class="mro34mbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:angle-double-left" {...props}></Icon>
