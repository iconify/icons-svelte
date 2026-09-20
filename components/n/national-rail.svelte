<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3qhh86ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3qhh86ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:national-rail" {...props}></Icon>
