<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl12y3b3s.css';
import '../../css/g/grg2vfnmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pl12y3b3s"/><path class="grg2vfnmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:paste-rtl" {...props}></Icon>
