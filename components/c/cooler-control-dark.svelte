<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c90rkqbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c90rkqbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cooler-control-dark" {...props}></Icon>
