<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha17z1bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ha17z1bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:fishing-pier" {...props}></Icon>
