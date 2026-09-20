<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mixc26bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mixc26bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hard-candy-in-wrapper" {...props}></Icon>
