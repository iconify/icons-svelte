<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_8agt07l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_8agt07l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hemisphere-line" {...props}></Icon>
