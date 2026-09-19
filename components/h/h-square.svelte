<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8fzehbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="j8fzehbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:h-square" {...props}></Icon>
