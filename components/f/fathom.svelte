<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tttrzcb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tttrzcb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fathom" {...props}></Icon>
