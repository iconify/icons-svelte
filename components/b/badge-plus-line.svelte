<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3_nkuuoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3_nkuuoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-plus-line" {...props}></Icon>
