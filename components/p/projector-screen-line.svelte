<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re1bh2b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re1bh2b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:projector-screen-line" {...props}></Icon>
