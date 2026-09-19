<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt18aubkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="mt18aubkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:quora" {...props}></Icon>
