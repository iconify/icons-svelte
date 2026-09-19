<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahkf60ncm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahkf60ncm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:certificate" {...props}></Icon>
