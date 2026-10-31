<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/b/bjsh7rmdv.css';
import '../../css/m/mrpjhzbvf.css';
import '../../css/k/kogpadc5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="bjsh7rmdv"/><path class="mrpjhzbvf wm-k"/><path class="kogpadc5i wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:git-graph" {...props}></Icon>
