<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/jjfd7rbye.css';
import '../../css/f/f1r26vbpu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFEM1KGbI"><g class="v3_i3wktz"><path class="jjfd7rbye"/><path class="f1r26vbpu"/></g></mask></defs><path mask="url(#SVGFEM1KGbI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:audit" {...props}></Icon>
