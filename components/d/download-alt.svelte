<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgmsu_7-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgmsu_7-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:download-alt" {...props}></Icon>
