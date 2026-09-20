<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnw4ovbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnw4ovbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-pin" {...props}></Icon>
