<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijw27cjpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ijw27cjpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-shrink" {...props}></Icon>
