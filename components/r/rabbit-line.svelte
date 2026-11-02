<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu8wy8bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu8wy8bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rabbit-line" {...props}></Icon>
