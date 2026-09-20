<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh1tldhks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fh1tldhks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-down-filled" {...props}></Icon>
