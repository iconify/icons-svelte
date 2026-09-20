<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu-l12apa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cu-l12apa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:news-paper-remix" {...props}></Icon>
