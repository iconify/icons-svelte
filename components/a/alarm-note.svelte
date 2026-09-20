<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzcdafbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzcdafbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alarm-note" {...props}></Icon>
