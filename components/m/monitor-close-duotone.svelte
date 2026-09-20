<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e3bk71n9p.css';
import '../../css/w/wt48mebuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e3bk71n9p"/><path class="wt48mebuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-close-duotone" {...props}></Icon>
