<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnuy-zbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnuy-zbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-plus" {...props}></Icon>
