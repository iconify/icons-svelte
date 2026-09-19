<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ildhqge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="b2ildhqge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:beach-slipper" {...props}></Icon>
