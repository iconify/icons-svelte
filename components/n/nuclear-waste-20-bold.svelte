<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs-k6d3fm.css';
import '../../css/c/c1--uvb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs-k6d3fm"/><path class="c1--uvb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-waste-20-bold" {...props}></Icon>
