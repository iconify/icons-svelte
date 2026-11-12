<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8h5bgb-m.css';
import '../../css/k/k8o447kzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8h5bgb-m"/><path class="k8o447kzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nimtable-light" {...props}></Icon>
