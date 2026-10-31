<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0jc5rbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0jc5rbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-check-fill-round" {...props}></Icon>
