<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uchecvbgp.css';
import '../../css/s/sryd7gbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uchecvbgp"/><path class="sryd7gbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gear-48-bold" {...props}></Icon>
