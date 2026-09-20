<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5nx4b1te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a5nx4b1te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:moon-cloud" {...props}></Icon>
