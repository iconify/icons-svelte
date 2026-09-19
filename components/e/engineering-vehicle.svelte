<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/j850wac-i.css';
import '../../css/n/n56_8z4jg.css';
import '../../css/o/ofkbvnbsv.css';
import '../../css/z/z6z3uibua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="j850wac-i"/><path class="n56_8z4jg"/><circle class="ofkbvnbsv"/><circle class="z6z3uibua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:engineering-vehicle" {...props}></Icon>
