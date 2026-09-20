<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jls4p8yza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jls4p8yza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bird-flying" {...props}></Icon>
