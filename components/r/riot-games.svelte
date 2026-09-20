<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axjgsy3nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axjgsy3nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:riot-games" {...props}></Icon>
