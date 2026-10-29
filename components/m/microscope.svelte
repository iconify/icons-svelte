<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s46ad_d8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s46ad_d8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:microscope" {...props}></Icon>
