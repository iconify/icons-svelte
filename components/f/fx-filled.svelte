<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydh90c3is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydh90c3is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fx-filled" {...props}></Icon>
