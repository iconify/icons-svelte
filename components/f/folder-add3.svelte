<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1dviszv.css';
import '../../css/w/w-6yckbxi.css';
import '../../css/j/jx_9pv92d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="w-6yckbxi"/><path class="jx_9pv92d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-add3" {...props}></Icon>
