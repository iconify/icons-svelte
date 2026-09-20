<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrq3cn4tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrq3cn4tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lutris" {...props}></Icon>
