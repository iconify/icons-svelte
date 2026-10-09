<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7gs-30zl.css';
import '../../css/h/h-sadvblf.css';
import '../../css/s/spu04ibth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n7gs-30zl"/><path class="h-sadvblf"/><path class="spu04ibth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kite-48" {...props}></Icon>
