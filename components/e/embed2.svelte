<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj6-xlb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":16};
const content = `<path class="xj6-xlb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:embed2" {...props}></Icon>
