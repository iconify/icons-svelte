<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt-0alp2o.css';
import '../../css/q/qrldk9bjb.css';
import '../../css/i/iqpkuk7ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bt-0alp2o"/><path class="qrldk9bjb"/><path class="iqpkuk7ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-minus-48-bold" {...props}></Icon>
