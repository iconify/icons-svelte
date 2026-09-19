<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/v/vw1o8d0ae.css';
import '../../css/b/bm6ci6bnn.css';
import '../../css/h/hd4mi7i3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="vw1o8d0ae"/><path class="bm6ci6bnn"/><path class="hd4mi7i3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:gastrointestinal" {...props}></Icon>
