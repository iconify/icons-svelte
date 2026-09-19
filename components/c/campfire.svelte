<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsd1-gkmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1022};
const content = `<path class="dsd1-gkmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:campfire" {...props}></Icon>
