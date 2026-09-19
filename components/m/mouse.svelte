<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wax2jmrhx.css';
import '../../css/a/a44ck8zrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wax2jmrhx"/><path class="a44ck8zrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mouse" {...props}></Icon>
