<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqioeeb_p.css';
import '../../css/r/r1w4d6azy.css';
import '../../css/n/n_x5vvvyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pqioeeb_p"/><path class="r1w4d6azy"/><path class="n_x5vvvyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-enterprise" {...props}></Icon>
