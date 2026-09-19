<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4o6kkbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":897};
const content = `<path class="g4o6kkbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:minigrin" {...props}></Icon>
