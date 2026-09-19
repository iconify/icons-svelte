<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/c/c1yjnaccy.css';
import '../../css/f/f1--t6a0g.css';
import '../../css/e/eyrc--b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="c1yjnaccy"/><path class="f1--t6a0g"/><path class="eyrc--b5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:gn-4x3" {...props}></Icon>
