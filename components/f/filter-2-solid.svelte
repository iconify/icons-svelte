<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjgzohr4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wjgzohr4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:filter-2-solid" {...props}></Icon>
