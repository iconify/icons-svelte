<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju7sv0aes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ju7sv0aes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:iphone-remix" {...props}></Icon>
