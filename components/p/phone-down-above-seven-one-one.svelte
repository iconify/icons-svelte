<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkbqpoy8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kkbqpoy8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-seven-one-one" {...props}></Icon>
