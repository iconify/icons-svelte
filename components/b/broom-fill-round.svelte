<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-o94abqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-o94abqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:broom-fill-round" {...props}></Icon>
