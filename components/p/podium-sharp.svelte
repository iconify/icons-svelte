<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgojmwbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgojmwbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:podium-sharp" {...props}></Icon>
