<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uah-6e1tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uah-6e1tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rocket-fill-round" {...props}></Icon>
