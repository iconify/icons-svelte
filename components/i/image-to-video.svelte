<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/r0hmkxtxf.css';
import '../../css/n/nz6ta7yil.css';
import '../../css/j/jvvu3bbeh.css';
import '../../css/i/i42jhdcnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0hmkxtxf"/><path class="nz6ta7yil"/><path class="jvvu3bbeh"/><path class="i42jhdcnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-to-video" {...props}></Icon>
