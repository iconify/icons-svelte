<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb2keo2id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tb2keo2id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:diamond-turn-right" {...props}></Icon>
