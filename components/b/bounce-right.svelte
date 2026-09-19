<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5y942p5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5y942p5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bounce-right" {...props}></Icon>
