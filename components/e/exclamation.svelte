<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlubp1u1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":1408};
const content = `<path class="wlubp1u1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:exclamation" {...props}></Icon>
