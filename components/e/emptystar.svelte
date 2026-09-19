<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca88xpb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":961};
const content = `<path class="ca88xpb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emptystar" {...props}></Icon>
