<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de6943wru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="de6943wru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:record" {...props}></Icon>
