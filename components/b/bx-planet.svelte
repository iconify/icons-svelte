<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nytgl6bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nytgl6bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-planet" {...props}></Icon>
