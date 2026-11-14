<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3y5qibll.css';
import '../../css/b/bxrcbrb3m.css';
import '../../css/r/r-qi2rbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p3y5qibll"/><path class="bxrcbrb3m"/><path class="r-qi2rbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minecraft-creeper-light" {...props}></Icon>
