<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrln9oh8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrln9oh8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-5-line" {...props}></Icon>
