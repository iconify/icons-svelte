<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-n5vvfhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u-n5vvfhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cube-fill" {...props}></Icon>
