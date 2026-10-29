<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndsaobw2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndsaobw2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-c" {...props}></Icon>
