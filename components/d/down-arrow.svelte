<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5waivb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j5waivb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:down-arrow" {...props}></Icon>
