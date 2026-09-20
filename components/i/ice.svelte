<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz7jn38ey.css';
import '../../css/y/ynkxq5xnv.css';
import '../../css/a/asevnlbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz7jn38ey"/><path class="ynkxq5xnv"/><path class="asevnlbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ice" {...props}></Icon>
