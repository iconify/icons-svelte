<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm2ivuwhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vm2ivuwhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pencil-and-apple" {...props}></Icon>
