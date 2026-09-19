<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1s_y2l-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1s_y2l-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:film-outline" {...props}></Icon>
