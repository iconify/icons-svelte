<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj_w50bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj_w50bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:baby" {...props}></Icon>
