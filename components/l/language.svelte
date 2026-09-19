<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iha5l2r0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iha5l2r0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:language" {...props}></Icon>
