<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcrsjzzif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcrsjzzif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alert-octagram" {...props}></Icon>
