<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1ckqlb3r.css';
import '../../css/l/lhsg4trxw.css';
import '../../css/o/ozsbau3sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y1ckqlb3r"/><path class="lhsg4trxw"/><path class="ozsbau3sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gavel-20-bold" {...props}></Icon>
