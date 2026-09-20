<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjvz-qrwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjvz-qrwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:emoji-2-fill" {...props}></Icon>
