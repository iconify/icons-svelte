<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybsjnpa-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybsjnpa-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:misskey-fill" {...props}></Icon>
