<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7ay1achv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7ay1achv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:flickr" {...props}></Icon>
