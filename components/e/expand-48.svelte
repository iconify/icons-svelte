<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf8xqzbqy.css';
import '../../css/p/pba0y-2ri.css';
import '../../css/m/m1-zbuhax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hf8xqzbqy"/><path class="pba0y-2ri"/><path class="m1-zbuhax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:expand-48" {...props}></Icon>
