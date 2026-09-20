<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmvjp89df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="jmvjp89df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-alt-storm-showers" {...props}></Icon>
