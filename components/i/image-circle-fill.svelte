<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0fu9qbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0fu9qbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-circle-fill" {...props}></Icon>
