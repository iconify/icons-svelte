<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pddsoc61y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pddsoc61y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:autobrr-dark" {...props}></Icon>
