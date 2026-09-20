<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcv3smdhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcv3smdhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:creative-commons-nc-fill" {...props}></Icon>
