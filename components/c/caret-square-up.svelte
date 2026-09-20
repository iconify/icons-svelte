<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a59iyablm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a59iyablm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:caret-square-up" {...props}></Icon>
