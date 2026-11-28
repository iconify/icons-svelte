<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auxxc2gzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auxxc2gzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-play-solid" {...props}></Icon>
