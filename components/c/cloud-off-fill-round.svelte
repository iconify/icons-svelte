<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8qqagbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8qqagbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-off-fill-round" {...props}></Icon>
