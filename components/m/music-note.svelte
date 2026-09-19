<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk72dvbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk72dvbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:music-note" {...props}></Icon>
