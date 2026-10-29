<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5yt5hneb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5yt5hneb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:recycle-solid" {...props}></Icon>
