<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iea6d-aqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iea6d-aqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-2-line" {...props}></Icon>
