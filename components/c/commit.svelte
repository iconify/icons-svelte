<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vae0u8-_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vae0u8-_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:commit" {...props}></Icon>
