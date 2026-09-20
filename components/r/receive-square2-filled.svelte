<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak7eg6csd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak7eg6csd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receive-square2-filled" {...props}></Icon>
