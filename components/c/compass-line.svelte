<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1m_6d7ct.css';
import '../../css/u/uo96j3bcz.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l1m_6d7ct"/><path class="clr-i-outline clr-i-outline-path-2 uo96j3bcz"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:compass-line" {...props}></Icon>
