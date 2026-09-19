<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6jyqbc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="j6jyqbc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:plug" {...props}></Icon>
