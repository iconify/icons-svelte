<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd0oxcbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd0oxcbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dots-fill" {...props}></Icon>
