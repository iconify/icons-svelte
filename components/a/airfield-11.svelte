<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul3pwpgog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ul3pwpgog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:airfield-11" {...props}></Icon>
