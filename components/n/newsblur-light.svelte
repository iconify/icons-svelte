<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnfr2fw6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dnfr2fw6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:newsblur-light" {...props}></Icon>
