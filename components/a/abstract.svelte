<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv9xkx0md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv9xkx0md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:abstract" {...props}></Icon>
