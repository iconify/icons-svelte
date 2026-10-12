<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teszfnbjc.css';
import '../../css/s/sktx1i8jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="teszfnbjc"/><path class="sktx1i8jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bandage-48" {...props}></Icon>
