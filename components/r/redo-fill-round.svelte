<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h356wee5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h356wee5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:redo-fill-round" {...props}></Icon>
