<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f75kumbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f75kumbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drink-fill" {...props}></Icon>
