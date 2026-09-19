<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5-3g4bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="a5-3g4bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:goforward-75" {...props}></Icon>
