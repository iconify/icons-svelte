<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh-qgz3bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh-qgz3bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-filled" {...props}></Icon>
