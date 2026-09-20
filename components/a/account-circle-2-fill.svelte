<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrf2le85t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrf2le85t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-circle-2-fill" {...props}></Icon>
