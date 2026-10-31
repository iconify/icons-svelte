<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxw0ohbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxw0ohbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-close-round" {...props}></Icon>
