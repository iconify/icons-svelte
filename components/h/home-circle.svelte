<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yorjo8b9o.css';
import '../../css/b/bhvzhcv4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yorjo8b9o"/><path class="bhvzhcv4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:home-circle" {...props}></Icon>
