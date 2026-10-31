<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw1cj3bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw1cj3bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-minus-round" {...props}></Icon>
