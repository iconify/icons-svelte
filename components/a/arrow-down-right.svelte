<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upbi2ob9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="upbi2ob9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-right" {...props}></Icon>
