<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnb11-bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jnb11-bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:roadsignleft" {...props}></Icon>
