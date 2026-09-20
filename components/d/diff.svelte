<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl_7wtbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="pl_7wtbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff" {...props}></Icon>
