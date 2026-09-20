<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tecn8zjex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tecn8zjex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:calendar-mark-solid" {...props}></Icon>
