<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu4n2224j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu4n2224j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-right2-filled" {...props}></Icon>
