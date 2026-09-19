<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhbx1kb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhbx1kb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pollen-dust" {...props}></Icon>
