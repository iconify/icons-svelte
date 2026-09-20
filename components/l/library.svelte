<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xia6zebwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="xia6zebwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:library" {...props}></Icon>
