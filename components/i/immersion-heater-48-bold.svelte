<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn87rsbwd.css';
import '../../css/l/laahlfxkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cn87rsbwd"/><path class="laahlfxkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:immersion-heater-48-bold" {...props}></Icon>
