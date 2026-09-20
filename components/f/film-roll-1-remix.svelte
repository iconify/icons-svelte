<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc587fb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sc587fb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:film-roll-1-remix" {...props}></Icon>
