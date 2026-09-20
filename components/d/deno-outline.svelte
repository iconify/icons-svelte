<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-viribkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n-viribkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:deno-outline" {...props}></Icon>
