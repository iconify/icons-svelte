<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqeas2b2i.css';
import '../../css/k/ks-k4jbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqeas2b2i"/><path class="ks-k4jbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:if-question-circle" {...props}></Icon>
