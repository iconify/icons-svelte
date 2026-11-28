<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1wiewb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1wiewb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:donut-heart" {...props}></Icon>
