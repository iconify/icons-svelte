<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5im1qbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1137,"height":1000};
const content = `<path class="c5im1qbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:comment" {...props}></Icon>
