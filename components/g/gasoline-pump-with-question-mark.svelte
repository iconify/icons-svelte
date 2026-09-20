<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srr1b7b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="srr1b7b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gasoline-pump-with-question-mark" {...props}></Icon>
