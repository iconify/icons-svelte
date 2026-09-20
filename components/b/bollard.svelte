<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf2ymx__o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uf2ymx__o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bollard" {...props}></Icon>
