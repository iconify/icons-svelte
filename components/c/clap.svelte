<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvwqk-blo.css';
import '../../css/a/a3vv8kymh.css';
import '../../css/g/g5s83bb7v.css';
import '../../css/f/flsl0ybgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nvwqk-blo"/><path class="a3vv8kymh"/><path class="g5s83bb7v"/><path class="flsl0ybgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:clap" {...props}></Icon>
