<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q31pl2bmr.css';
import '../../css/y/y0lh2dbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q31pl2bmr"/><path class="y0lh2dbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-star-line" {...props}></Icon>
