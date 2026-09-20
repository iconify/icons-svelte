<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xknqbcc3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xknqbcc3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:left-arrow-1" {...props}></Icon>
