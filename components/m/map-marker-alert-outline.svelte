<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbapx21sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbapx21sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-marker-alert-outline" {...props}></Icon>
