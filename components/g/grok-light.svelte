<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar6bwwbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ar6bwwbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:grok-light" {...props}></Icon>
