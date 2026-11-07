<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xldk15bbn.css';
import '../../css/u/uee4y3m1v.css';
import '../../css/e/esmj5zbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xldk15bbn"/><path class="uee4y3m1v"/><path class="esmj5zbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-line-bold-duotone" {...props}></Icon>
