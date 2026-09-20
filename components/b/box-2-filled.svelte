<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbgym7_im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbgym7_im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:box-2-filled" {...props}></Icon>
