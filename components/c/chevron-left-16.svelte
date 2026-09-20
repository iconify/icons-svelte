<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd795fxhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xd795fxhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-left-16" {...props}></Icon>
