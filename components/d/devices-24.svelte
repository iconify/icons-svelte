<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry2iipgfe.css';
import '../../css/p/p1xj-fcxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry2iipgfe"/><path class="p1xj-fcxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:devices-24" {...props}></Icon>
