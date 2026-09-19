<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc8-4tb2b.css';
import '../../css/n/nw-f-lb0x.css';
import '../../css/t/t_p41ydtf.css';
import '../../css/a/advo7kb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="nw-f-lb0x"/><path class="t_p41ydtf"/><path class="advo7kb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:control-twotone" {...props}></Icon>
