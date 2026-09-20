<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqqs8_lie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqqs8_lie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:critical-light" {...props}></Icon>
