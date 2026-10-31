<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf76-bcuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf76-bcuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:quote-left-round" {...props}></Icon>
