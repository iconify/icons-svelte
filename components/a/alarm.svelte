<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8__0mb4m.css';
import '../../css/b/bb_scruft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m8__0mb4m"/><path class="bb_scruft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:alarm" {...props}></Icon>
