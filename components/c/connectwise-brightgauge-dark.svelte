<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2wqhl8qw.css';
import '../../css/k/kjglpe2ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x2wqhl8qw"/><path class="kjglpe2ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:connectwise-brightgauge-dark" {...props}></Icon>
