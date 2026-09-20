<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xocow_b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xocow_b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:logout-outline" {...props}></Icon>
