<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/fuz479bot.css';
import '../../css/f/fcp723b9j.css';
import '../../css/q/qefv847_y.css';
import '../../css/g/gwafzf_sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="fuz479bot"/><path class="fcp723b9j"/><circle class="qefv847_y"/><circle class="gwafzf_sr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:owl" {...props}></Icon>
