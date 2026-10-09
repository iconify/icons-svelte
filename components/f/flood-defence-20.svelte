<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laitt1gtv.css';
import '../../css/t/tqdr_mbdb.css';
import '../../css/k/k153fdm9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="laitt1gtv"/><path class="tqdr_mbdb"/><path class="k153fdm9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flood-defence-20" {...props}></Icon>
