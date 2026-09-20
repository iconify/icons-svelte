<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgemnd1nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<circle class="cgemnd1nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:circle" {...props}></Icon>
