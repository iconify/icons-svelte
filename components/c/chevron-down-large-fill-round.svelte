<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f31cmbbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f31cmbbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-down-large-fill-round" {...props}></Icon>
