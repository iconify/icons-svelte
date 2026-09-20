<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-ymqwbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-ymqwbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-youtube-filled" {...props}></Icon>
