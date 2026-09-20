<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5d55xbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="o5d55xbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:barrier-11" {...props}></Icon>
