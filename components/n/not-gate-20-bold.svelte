<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuil0dbas.css';
import '../../css/d/dzyouclrc.css';
import '../../css/c/cum2y9o2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zuil0dbas"/><path class="dzyouclrc"/><path class="cum2y9o2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:not-gate-20-bold" {...props}></Icon>
