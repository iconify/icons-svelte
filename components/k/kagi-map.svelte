<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ralt7bb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ralt7bb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:kagi-map" {...props}></Icon>
