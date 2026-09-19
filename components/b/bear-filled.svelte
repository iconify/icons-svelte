<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8yo2xlul.css';
import '../../css/w/wth0vybwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8yo2xlul"/><path class="wth0vybwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bear-filled" {...props}></Icon>
