<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz8y_cqlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iz8y_cqlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forauth-light" {...props}></Icon>
