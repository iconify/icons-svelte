<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eie8mt2ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="eie8mt2ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:divide-square" {...props}></Icon>
