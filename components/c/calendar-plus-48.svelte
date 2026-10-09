<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pycxs8orj.css';
import '../../css/z/zejh6zddn.css';
import '../../css/i/iun1bib_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="zejh6zddn"/><path class="iun1bib_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-plus-48" {...props}></Icon>
