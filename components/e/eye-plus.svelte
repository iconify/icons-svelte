<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eziq8xbrj.css';
import '../../css/s/sb7vsacsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eziq8xbrj"/><path class="sb7vsacsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:eye-plus" {...props}></Icon>
