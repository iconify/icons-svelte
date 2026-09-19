<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgrfg_3le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgrfg_3le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:apple-airpods-pro" {...props}></Icon>
