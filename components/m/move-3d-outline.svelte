<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqkdk3e9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqkdk3e9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-3d-outline" {...props}></Icon>
