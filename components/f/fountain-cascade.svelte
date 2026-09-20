<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we_y37bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="we_y37bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fountain-cascade" {...props}></Icon>
