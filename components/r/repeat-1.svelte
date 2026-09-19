<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwdrfmbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="kwdrfmbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:repeat-1" {...props}></Icon>
