<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg9kfeu9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fg9kfeu9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:novelwriter" {...props}></Icon>
