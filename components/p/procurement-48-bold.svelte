<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugy_83khr.css';
import '../../css/t/trs0klbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ugy_83khr"/><path class="trs0klbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:procurement-48-bold" {...props}></Icon>
