<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wahtxdb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wahtxdb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:megaphone-filled" {...props}></Icon>
