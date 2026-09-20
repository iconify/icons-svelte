<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/svknz3bwq.css';
import '../../css/n/npr06hbbs.css';
import '../../css/b/bek0hpq9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="svknz3bwq"/><path class="npr06hbbs"/><path class="bek0hpq9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fish" {...props}></Icon>
