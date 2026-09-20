<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qthr_h6oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qthr_h6oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:microphone-slash" {...props}></Icon>
