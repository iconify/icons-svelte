<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn48uir4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn48uir4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-monday" {...props}></Icon>
