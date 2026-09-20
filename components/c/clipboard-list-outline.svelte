<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loyubsbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loyubsbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-list-outline" {...props}></Icon>
