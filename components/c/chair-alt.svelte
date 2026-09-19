<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miifqw2bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1664};
const content = `<path class="miifqw2bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:chair-alt" {...props}></Icon>
