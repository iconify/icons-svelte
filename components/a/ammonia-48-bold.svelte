<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlpv10bkk.css';
import '../../css/a/aai7kpb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vlpv10bkk"/><path class="aai7kpb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammonia-48-bold" {...props}></Icon>
