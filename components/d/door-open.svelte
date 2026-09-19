<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpop_tbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="hpop_tbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:door-open" {...props}></Icon>
