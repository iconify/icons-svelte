<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2kgjwa6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2kgjwa6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-chevron-right-round" {...props}></Icon>
