<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auiwbcdbq.css';
import '../../css/x/xafj45btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auiwbcdbq"/><path class="xafj45btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lunc" {...props}></Icon>
