<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7xa7nbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7xa7nbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:moon-fill" {...props}></Icon>
