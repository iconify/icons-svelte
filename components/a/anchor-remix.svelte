<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hll991hcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hll991hcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:anchor-remix" {...props}></Icon>
