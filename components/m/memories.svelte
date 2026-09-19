<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy7uvjurt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cy7uvjurt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:memories" {...props}></Icon>
