<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7r425_gi.css';
import '../../css/q/qgbgttb3i.css';
import '../../css/g/gtes6eb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7r425_gi"/><path class="qgbgttb3i"/><path class="gtes6eb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:feed-duotone" {...props}></Icon>
