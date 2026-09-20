<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osrlgunlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osrlgunlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-off" {...props}></Icon>
