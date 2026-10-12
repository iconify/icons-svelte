<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijtm4crnn.css';
import '../../css/a/afxexlctq.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ijtm4crnn"/><path class="afxexlctq"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-plus-48-bold" {...props}></Icon>
