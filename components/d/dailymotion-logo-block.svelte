<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntvn5jw-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntvn5jw-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:dailymotion-logo-block" {...props}></Icon>
