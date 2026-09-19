<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcytv_bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcytv_bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:onedrive" {...props}></Icon>
