<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b53xp0bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b53xp0bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:refrigerator-remix" {...props}></Icon>
