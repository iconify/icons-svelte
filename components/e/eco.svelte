<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu-3omdxe.css';
import '../../css/q/qjqgoubck.css';
import '../../css/b/bp_58fjhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu-3omdxe"/><path class="qjqgoubck"/><path class="bp_58fjhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eco" {...props}></Icon>
