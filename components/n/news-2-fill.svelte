<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2q08xbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2q08xbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:news-2-fill" {...props}></Icon>
