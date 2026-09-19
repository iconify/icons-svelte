<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/ozbdiq3aa.css';
import '../../css/g/g-zi73ava.css';
import '../../css/g/g698gzb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="ozbdiq3aa"/><path class="g-zi73ava"/><path class="g698gzb4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:iphone" {...props}></Icon>
