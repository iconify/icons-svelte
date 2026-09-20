<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9j4y2v-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q9j4y2v-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-chip-1-solid" {...props}></Icon>
