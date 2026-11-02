<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh5u8_bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh5u8_bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-output-line" {...props}></Icon>
