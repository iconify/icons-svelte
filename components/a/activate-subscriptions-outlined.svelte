<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_b8-8a_m.css';
import '../../css/y/ydl-jxb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_b8-8a_m"/><path class="ydl-jxb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:activate-subscriptions-outlined" {...props}></Icon>
