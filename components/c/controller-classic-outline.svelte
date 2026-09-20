<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbbcgtovc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbbcgtovc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:controller-classic-outline" {...props}></Icon>
