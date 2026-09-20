<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbz6o0bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbz6o0bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:move-down-right" {...props}></Icon>
