<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slf8enbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slf8enbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:notepad-text" {...props}></Icon>
