<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1fzk0bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j1fzk0bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ok-hand-solid" {...props}></Icon>
