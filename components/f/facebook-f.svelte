<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc9m1-b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1664};
const content = `<path class="nc9m1-b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:facebook-f" {...props}></Icon>
