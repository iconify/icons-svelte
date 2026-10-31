<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnyugtbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnyugtbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bookmark-plus-round" {...props}></Icon>
