<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6q8jg6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aa6q8jg6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frisbee" {...props}></Icon>
