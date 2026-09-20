<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1k-wxb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1k-wxb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-send" {...props}></Icon>
