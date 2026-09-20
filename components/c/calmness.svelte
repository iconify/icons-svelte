<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy0lpbywg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uy0lpbywg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calmness" {...props}></Icon>
