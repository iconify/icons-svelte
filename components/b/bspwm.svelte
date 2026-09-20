<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7d2ywa-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7d2ywa-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bspwm" {...props}></Icon>
