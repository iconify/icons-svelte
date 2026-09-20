<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqy47e33q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqy47e33q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clipboard-data-filled" {...props}></Icon>
