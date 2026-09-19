<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yorjo8b9o.css';
import '../../css/s/sq7litb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yorjo8b9o"/><path class="sq7litb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:home-add" {...props}></Icon>
