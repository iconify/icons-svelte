<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br17oobhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="br17oobhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:controllerps" {...props}></Icon>
