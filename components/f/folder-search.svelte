<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-ajg0yqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-ajg0yqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-search" {...props}></Icon>
