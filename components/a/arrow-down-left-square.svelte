<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evgd5di7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="evgd5di7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-left-square" {...props}></Icon>
