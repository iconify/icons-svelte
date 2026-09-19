<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5c_go20t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p5c_go20t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:algolia" {...props}></Icon>
