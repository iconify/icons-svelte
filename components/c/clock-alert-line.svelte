<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncirv0fnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncirv0fnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-alert-line" {...props}></Icon>
