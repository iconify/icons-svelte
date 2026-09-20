<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed6qwbapg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed6qwbapg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:history" {...props}></Icon>
