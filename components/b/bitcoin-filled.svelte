<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7ogi1brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c7ogi1brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bitcoin-filled" {...props}></Icon>
