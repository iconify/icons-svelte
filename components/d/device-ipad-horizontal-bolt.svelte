<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko8ti6cjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko8ti6cjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-bolt" {...props}></Icon>
