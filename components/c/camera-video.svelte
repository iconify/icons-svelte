<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvnqahb0g.css';
import '../../css/b/bhdfqnbsu.css';
import '../../css/k/k783hdbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rvnqahb0g"><path class="bhdfqnbsu"/><path class="k783hdbat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:camera-video" {...props}></Icon>
