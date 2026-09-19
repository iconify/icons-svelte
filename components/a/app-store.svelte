<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujf0-3dpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujf0-3dpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:app-store" {...props}></Icon>
