<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo7ddhbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo7ddhbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:layers-outline" {...props}></Icon>
