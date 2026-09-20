<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvrkmebkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvrkmebkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:music-pin" {...props}></Icon>
