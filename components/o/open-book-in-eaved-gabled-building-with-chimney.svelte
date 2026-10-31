<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp46v6-0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xp46v6-0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-book-in-eaved-gabled-building-with-chimney" {...props}></Icon>
