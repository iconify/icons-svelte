<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xit-_fb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xit-_fb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-search-fill-round" {...props}></Icon>
