<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cibn_julo.css';
import '../../css/e/epdoheazy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cibn_julo"/><path class="epdoheazy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:memory-chip-48-bold" {...props}></Icon>
