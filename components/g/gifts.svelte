<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi36_vj3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="wi36_vj3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:gifts" {...props}></Icon>
