<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yksjou5qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="yksjou5qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:list-ordered" {...props}></Icon>
