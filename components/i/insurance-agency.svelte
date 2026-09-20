<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccbd5bcee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ccbd5bcee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:insurance-agency" {...props}></Icon>
