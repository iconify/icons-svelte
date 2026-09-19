<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pghknmpwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pghknmpwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:f" {...props}></Icon>
