<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/j78p-caua.css';
import '../../css/v/vutiidbtf.css';
import '../../css/c/ck9sfsb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="j78p-caua"/><circle class="vutiidbtf"/><path class="ck9sfsb3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:git-compare" {...props}></Icon>
