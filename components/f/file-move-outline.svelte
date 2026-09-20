<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3hh_23yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3hh_23yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-move-outline" {...props}></Icon>
