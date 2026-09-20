<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cfxjvzb8q.css';
import '../../css/x/x1kdd3bji.css';
import '../../css/b/b6eynkbex.css';
import '../../css/n/nuw1jpblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cfxjvzb8q"/><path class="x1kdd3bji"/><path class="b6eynkbex"/><path class="nuw1jpblt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:filter-2" {...props}></Icon>
