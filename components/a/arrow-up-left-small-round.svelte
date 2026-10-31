<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk_ur4bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk_ur4bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-left-small-round" {...props}></Icon>
