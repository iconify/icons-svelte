<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty_ooxbvp.css';
import '../../css/t/tof83qbtg.css';
import '../../css/k/kgj1lsauv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="ty_ooxbvp"/><circle class="tof83qbtg"/><circle class="kgj1lsauv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:ellipsis-v" {...props}></Icon>
