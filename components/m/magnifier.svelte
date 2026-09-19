<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urh4f7bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="urh4f7bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:magnifier" {...props}></Icon>
