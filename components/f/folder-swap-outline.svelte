<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hahi55pcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hahi55pcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-swap-outline" {...props}></Icon>
