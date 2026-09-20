<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh6odd6ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="wh6odd6ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:beach-11" {...props}></Icon>
