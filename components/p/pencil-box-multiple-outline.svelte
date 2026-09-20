<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gos-uetpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gos-uetpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil-box-multiple-outline" {...props}></Icon>
