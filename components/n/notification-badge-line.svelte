<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko4jtjbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko4jtjbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-badge-line" {...props}></Icon>
