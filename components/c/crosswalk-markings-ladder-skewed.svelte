<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edzsecg7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="edzsecg7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crosswalk-markings-ladder-skewed" {...props}></Icon>
