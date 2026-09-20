<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhb2l5b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhb2l5b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:atom-outline" {...props}></Icon>
