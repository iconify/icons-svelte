<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd4ui224u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pd4ui224u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pretzel-with-salt" {...props}></Icon>
