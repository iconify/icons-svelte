<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o124r16ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="o124r16ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-turn-right-down" {...props}></Icon>
