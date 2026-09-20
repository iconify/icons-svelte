<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz5sdrwre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz5sdrwre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:channel-add" {...props}></Icon>
