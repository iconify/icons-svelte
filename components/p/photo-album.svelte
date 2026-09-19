<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv9q63bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv9q63bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:photo-album" {...props}></Icon>
