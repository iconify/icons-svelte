<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnytfib0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="gnytfib0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:binary" {...props}></Icon>
