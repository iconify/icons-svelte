<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahudrcy8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahudrcy8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:maximize7-filled" {...props}></Icon>
