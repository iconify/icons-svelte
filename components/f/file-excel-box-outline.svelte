<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9piq1wjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9piq1wjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-excel-box-outline" {...props}></Icon>
