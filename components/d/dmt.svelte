<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-f8k3blw.css';
import '../../css/a/a4zhphb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-f8k3blw"/><path class="a4zhphb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dmt" {...props}></Icon>
