<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3_f12b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3_f12b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-search-outline" {...props}></Icon>
