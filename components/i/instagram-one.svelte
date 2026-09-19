<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly6jl_bkj.css';
import '../../css/a/aoabsmt9b.css';
import '../../css/f/fdw87rbat.css';
import '../../css/n/n9-l1jfhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ly6jl_bkj"><circle class="aoabsmt9b"/><rect class="fdw87rbat"/><path class="n9-l1jfhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:instagram-one" {...props}></Icon>
