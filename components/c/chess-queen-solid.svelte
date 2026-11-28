<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejdqt1mgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejdqt1mgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chess-queen-solid" {...props}></Icon>
