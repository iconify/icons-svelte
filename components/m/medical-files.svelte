<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/k/krfehbkwe.css';
import '../../css/w/wobtdmkua.css';
import '../../css/k/kut0iebfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="krfehbkwe"/><path class="wobtdmkua"/><path class="kut0iebfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:medical-files" {...props}></Icon>
