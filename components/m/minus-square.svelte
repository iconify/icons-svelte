<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ublemccmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ublemccmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:minus-square" {...props}></Icon>
