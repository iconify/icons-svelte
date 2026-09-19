<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpw5bfokz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="jpw5bfokz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cc-discover" {...props}></Icon>
