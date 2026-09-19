<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sg937_1md.css';
import '../../css/b/bbthzgo7i.css';
import '../../css/j/jef6gtb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="sg937_1md"/><path class="bbthzgo7i"/><path clip-rule="evenodd" class="jef6gtb-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:painted-eggshell" {...props}></Icon>
