<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n62a64b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n62a64b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:next" {...props}></Icon>
