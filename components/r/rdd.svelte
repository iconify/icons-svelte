<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dxla8wbho.css';
import '../../css/m/md286fbip.css';
import '../../css/w/wgvvon-ub.css';
import '../../css/d/dki4y58rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="dxla8wbho"/><g class="md286fbip"><path class="wgvvon-ub"/><path class="dki4y58rp"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:rdd" {...props}></Icon>
