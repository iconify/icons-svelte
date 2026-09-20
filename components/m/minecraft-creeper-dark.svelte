<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8a6uobym.css';
import '../../css/s/sz2d54b8l.css';
import '../../css/d/dfc8zzqzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g8a6uobym"/><path class="sz2d54b8l"/><path class="dfc8zzqzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minecraft-creeper-dark" {...props}></Icon>
