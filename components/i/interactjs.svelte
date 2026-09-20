<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm9o7ixyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm9o7ixyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:interactjs" {...props}></Icon>
