<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn53xabsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cn53xabsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pigpena" {...props}></Icon>
