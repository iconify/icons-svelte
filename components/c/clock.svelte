<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7s8sbcsh.css';
import '../../css/x/xb9g71azj.css';
import '../../css/i/iuk8uv24h.css';
import '../../css/g/geq_d8kpo.css';
import '../../css/w/wzjalqi7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7s8sbcsh wm-k"/><path class="wm-k xb9g71azj"/><path class="iuk8uv24h wm-a"/><path class="geq_d8kpo wm-a"/><path class="wm-a wzjalqi7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:clock" {...props}></Icon>
