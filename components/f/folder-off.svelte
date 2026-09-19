<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnu7jpalj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnu7jpalj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-off" {...props}></Icon>
