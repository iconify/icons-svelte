<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/g/g-wkuab2i.css';
import '../../css/n/n0zqm8odz.css';
import '../../css/y/yh8iq_b5d.css';
import '../../css/b/b7nrt6bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="g-wkuab2i"/><path class="n0zqm8odz"/><path class="yh8iq_b5d"/><path class="b7nrt6bdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:enquire" {...props}></Icon>
