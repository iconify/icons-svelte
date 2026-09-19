<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/i/i4qf59b1a.css';
import '../../css/f/fanud-8su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="i4qf59b1a"/><path class="fanud-8su"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:icecream" {...props}></Icon>
