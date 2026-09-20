<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cstzu4b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="cstzu4b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:jet-skiing" {...props}></Icon>
