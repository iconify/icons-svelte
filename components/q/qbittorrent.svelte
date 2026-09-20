<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd2nb4bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd2nb4bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qbittorrent" {...props}></Icon>
