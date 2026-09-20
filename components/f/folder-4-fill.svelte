<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-65o2amg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-65o2amg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-4-fill" {...props}></Icon>
