<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxq_49bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jxq_49bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can-with-spray-and-arrow-right-above-arrow-left" {...props}></Icon>
