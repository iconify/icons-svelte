<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tztkndb_y.css';
import '../../css/u/ubixxqbpx.css';
import '../../css/x/xnnvlwb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tztkndb_y"/><path class="ubixxqbpx"/><path class="xnnvlwb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cave-20" {...props}></Icon>
