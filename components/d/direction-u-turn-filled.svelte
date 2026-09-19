<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saty3nwhh.css';
import '../../css/n/nhm009g7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="saty3nwhh"/><path class="nhm009g7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-u-turn-filled" {...props}></Icon>
