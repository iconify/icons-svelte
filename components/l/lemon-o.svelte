<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfzas2b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="cfzas2b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:lemon-o" {...props}></Icon>
