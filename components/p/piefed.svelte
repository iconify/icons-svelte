<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ploysl_qi.css';
import '../../css/j/jlgzaobtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ploysl_qi"/><path class="jlgzaobtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piefed" {...props}></Icon>
