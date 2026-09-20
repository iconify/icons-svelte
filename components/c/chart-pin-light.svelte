<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/t/tz9-5ubyh.css';
import '../../css/h/h2fe-ksvz.css';
import '../../css/g/g38jmdb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="tz9-5ubyh"/><path class="h2fe-ksvz"/><circle class="g38jmdb2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chart-pin-light" {...props}></Icon>
