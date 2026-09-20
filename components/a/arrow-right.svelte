<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehdhxkbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehdhxkbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrow-right" {...props}></Icon>
