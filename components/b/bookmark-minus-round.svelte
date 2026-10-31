<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al_q3lsyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al_q3lsyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bookmark-minus-round" {...props}></Icon>
