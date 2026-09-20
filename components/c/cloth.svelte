<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osa6iacrl.css';
import '../../css/v/vv3o_rb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="osa6iacrl"/><path class="vv3o_rb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:cloth" {...props}></Icon>
