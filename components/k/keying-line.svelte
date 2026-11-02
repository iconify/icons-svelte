<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca45o2iyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca45o2iyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:keying-line" {...props}></Icon>
