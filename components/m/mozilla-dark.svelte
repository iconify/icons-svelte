<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg6q3ebhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kg6q3ebhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mozilla-dark" {...props}></Icon>
