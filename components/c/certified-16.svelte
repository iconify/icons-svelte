<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnb1mxbou.css';
import '../../css/q/qxw4ulbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qnb1mxbou"/><path clip-rule="evenodd" class="qxw4ulbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:certified-16" {...props}></Icon>
