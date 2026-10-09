<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnazeqbdf.css';
import '../../css/v/vihqj-brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lnazeqbdf"/><path class="vihqj-brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:podium-20" {...props}></Icon>
