<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7gaivhfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d7gaivhfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:building-2-fill" {...props}></Icon>
