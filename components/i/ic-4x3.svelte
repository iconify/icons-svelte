<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/r/rt8_ymbfa.css';
import '../../css/z/zh84q581l.css';
import '../../css/f/fml2hgb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="rt8_ymbfa"/><path class="zh84q581l"/><path class="fml2hgb5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ic-4x3" {...props}></Icon>
