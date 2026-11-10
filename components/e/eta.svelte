<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vag4pcbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vag4pcbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:eta" {...props}></Icon>
