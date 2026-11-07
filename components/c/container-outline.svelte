<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us4-9fqqe.css';
import '../../css/o/o1z7omb5q.css';
import '../../css/f/fo4-y40vu.css';
import '../../css/s/sg53hmyvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us4-9fqqe"/><path class="o1z7omb5q"/><path class="fo4-y40vu"/><path class="sg53hmyvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:container-outline" {...props}></Icon>
