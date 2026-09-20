<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed67yly0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed67yly0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mixtral-line" {...props}></Icon>
