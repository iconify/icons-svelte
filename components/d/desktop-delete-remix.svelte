<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1izhibvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a1izhibvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:desktop-delete-remix" {...props}></Icon>
