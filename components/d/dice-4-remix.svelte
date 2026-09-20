<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/askomeufq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="askomeufq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dice-4-remix" {...props}></Icon>
