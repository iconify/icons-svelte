<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5996na3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u5996na3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-curvy-up-down-1" {...props}></Icon>
