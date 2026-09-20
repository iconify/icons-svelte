<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pomcvvbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pomcvvbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forauth-dark" {...props}></Icon>
