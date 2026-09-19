<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng_fvcb6m.css';
import '../../css/v/vhybsjbtm.css';
import '../../css/c/cb92fbcyb.css';
import '../../css/c/cxr8jgpdc.css';
import '../../css/j/j1a_6bqzs.css';
import '../../css/u/u68l7sika.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ng_fvcb6m"/><circle class="vhybsjbtm"/><circle class="cb92fbcyb"/><circle class="cxr8jgpdc"/><circle class="j1a_6bqzs"/><circle class="u68l7sika"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-multitype" {...props}></Icon>
