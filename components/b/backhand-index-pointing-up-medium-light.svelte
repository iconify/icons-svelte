<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ixwxc1b2r.css';
import '../../css/y/ygh_macxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ixwxc1b2r"/><path clip-rule="evenodd" class="ygh_macxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:backhand-index-pointing-up-medium-light" {...props}></Icon>
