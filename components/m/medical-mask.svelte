<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/f6cmulb-y.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/q/q18shsb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6cmulb-y"/><circle class="shu3xdl9q"/><path class="q18shsb-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:medical-mask" {...props}></Icon>
