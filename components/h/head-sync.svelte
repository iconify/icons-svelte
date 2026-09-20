<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0ja_42gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0ja_42gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-sync" {...props}></Icon>
