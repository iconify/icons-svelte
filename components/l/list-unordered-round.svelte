<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfdd8xbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfdd8xbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-unordered-round" {...props}></Icon>
