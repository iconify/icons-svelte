<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v194byb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v194byb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-with-shine" {...props}></Icon>
