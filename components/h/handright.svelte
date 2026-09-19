<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trcjn3b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":704};
const content = `<path class="trcjn3b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:handright" {...props}></Icon>
