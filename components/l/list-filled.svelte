<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7i3kf9ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7i3kf9ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:list-filled" {...props}></Icon>
