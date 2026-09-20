<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdvrx72kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pdvrx72kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffee-mug-with-steam" {...props}></Icon>
