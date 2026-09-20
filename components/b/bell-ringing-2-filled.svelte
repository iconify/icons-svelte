<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8omf1bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8omf1bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-ringing-2-filled" {...props}></Icon>
