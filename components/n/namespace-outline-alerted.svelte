<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_yhajbgl.css';
import '../../css/s/s_tecendb.css';
import '../../css/y/yiybycb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="h_yhajbgl"/><path class="s_tecendb"/><path class="yiybycb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:namespace-outline-alerted" {...props}></Icon>
