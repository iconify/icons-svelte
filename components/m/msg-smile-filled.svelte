<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvfoi7ylk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvfoi7ylk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:msg-smile-filled" {...props}></Icon>
