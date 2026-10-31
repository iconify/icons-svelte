<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw0ourbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw0ourbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-b-fill-round" {...props}></Icon>
