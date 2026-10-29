<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9fb-ccxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9fb-ccxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chess-solid" {...props}></Icon>
