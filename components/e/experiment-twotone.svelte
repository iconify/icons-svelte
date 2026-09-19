<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odtla-seg.css';
import '../../css/n/ns3hbpbni.css';
import '../../css/p/ppyfuefwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="odtla-seg"/><path class="ns3hbpbni"/><path class="ppyfuefwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:experiment-twotone" {...props}></Icon>
