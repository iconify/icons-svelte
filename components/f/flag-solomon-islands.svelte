<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wism3vaym.css';
import '../../css/a/a8zg1pdpv.css';
import '../../css/b/b80t6qbns.css';
import '../../css/m/m50idfmqp.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wism3vaym"/><path class="a8zg1pdpv"/><path class="b80t6qbns"/><path class="m50idfmqp"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-solomon-islands" {...props}></Icon>
