<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgdsozb-t.css';
import '../../css/s/scwdfi6dx.css';
import '../../css/p/pb060eflr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bgdsozb-t"/><path class="scwdfi6dx"/><path class="pb060eflr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-20-bold" {...props}></Icon>
