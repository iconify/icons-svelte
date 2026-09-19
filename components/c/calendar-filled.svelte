<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puzsmobar.css';
import '../../css/n/npj2p4b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puzsmobar"/><path clip-rule="evenodd" class="npj2p4b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:calendar-filled" {...props}></Icon>
