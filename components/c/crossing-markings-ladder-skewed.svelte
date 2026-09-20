<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlymt9bdv.css';
import '../../css/u/ufp6rz5fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hlymt9bdv"/><path class="ufp6rz5fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:crossing-markings-ladder-skewed" {...props}></Icon>
