<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaj_3nngg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaj_3nngg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:merge-fill" {...props}></Icon>
