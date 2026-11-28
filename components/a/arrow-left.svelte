<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrm8teb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrm8teb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:arrow-left" {...props}></Icon>
