<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbqw558-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbqw558-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qi" {...props}></Icon>
