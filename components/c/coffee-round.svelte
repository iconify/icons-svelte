<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oobjjsbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oobjjsbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:coffee-round" {...props}></Icon>
