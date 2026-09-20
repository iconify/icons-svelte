<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppoewyanq.css';
import '../../css/m/mq10tpb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ppoewyanq"/><path class="mq10tpb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-supabase" {...props}></Icon>
