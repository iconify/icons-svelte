<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjo5k1bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjo5k1bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:previous-filled" {...props}></Icon>
