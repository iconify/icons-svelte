<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwmncibou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iwmncibou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:module-puzzle-2" {...props}></Icon>
