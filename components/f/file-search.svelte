<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3ffuob8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3ffuob8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-search" {...props}></Icon>
