<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlv0u0bzu.css';
import '../../css/w/wyuz1vbhu.css';
import '../../css/y/ynjpy6sjz.css';
import '../../css/m/mil8c4_7q.css';
import '../../css/o/oiypdpdrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vlv0u0bzu"/><path class="wyuz1vbhu"/><path class="ynjpy6sjz"/><path class="mil8c4_7q"/><path class="oiypdpdrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:reconciliation-twotone" {...props}></Icon>
