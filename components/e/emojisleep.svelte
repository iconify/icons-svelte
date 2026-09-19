<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzn7p-lkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mzn7p-lkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emojisleep" {...props}></Icon>
