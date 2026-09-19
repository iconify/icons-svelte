<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ub2coxuon.css';
import '../../css/s/sisnjrobj.css';
import '../../css/a/auq61abfx.css';
import '../../css/w/w592iwlnf.css';
import '../../css/q/qgovcdcyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ub2coxuon"/><path clip-rule="evenodd" class="sisnjrobj"/><path class="auq61abfx"/><path clip-rule="evenodd" class="w592iwlnf"/><path class="qgovcdcyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:path-bold" {...props}></Icon>
