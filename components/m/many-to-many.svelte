<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/j/jy1imkqad.css';
import '../../css/j/jmr6mcefv.css';
import '../../css/t/tusq8sbym.css';
import '../../css/l/l9ul_bcga.css';
import '../../css/t/tgiuuc7fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="jy1imkqad"/><path class="jmr6mcefv"/><path class="tusq8sbym"/><path class="l9ul_bcga"/><path class="tgiuuc7fp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:many-to-many" {...props}></Icon>
