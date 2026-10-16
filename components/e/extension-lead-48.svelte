<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um_1f_zem.css';
import '../../css/t/txa3dwb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="um_1f_zem"/><path class="txa3dwb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:extension-lead-48" {...props}></Icon>
