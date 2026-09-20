<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s10jxb77c.css';
import '../../css/q/q0ne03bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s10jxb77c"/><path class="q0ne03bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:clh" {...props}></Icon>
