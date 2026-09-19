<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjapq3bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjapq3bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:moon-fill" {...props}></Icon>
