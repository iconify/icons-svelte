<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eob-z-l-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eob-z-l-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-line-round" {...props}></Icon>
