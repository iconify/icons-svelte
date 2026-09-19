<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsfyf4bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hsfyf4bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:goforward-15" {...props}></Icon>
