<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvktx1bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvktx1bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-off" {...props}></Icon>
