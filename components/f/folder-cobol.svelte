<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhg495fle.css';
import '../../css/g/gb0t1hblg.css';
import '../../css/j/jje-lsbfh.css';
import '../../css/u/uslwxsbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nhg495fle"/><g class="gb0t1hblg"><path class="jje-lsbfh"/><path class="uslwxsbwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-cobol" {...props}></Icon>
