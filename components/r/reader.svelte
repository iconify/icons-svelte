<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b66p46a9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b66p46a9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:reader" {...props}></Icon>
