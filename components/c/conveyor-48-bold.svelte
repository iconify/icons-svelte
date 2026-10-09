<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqf5v4byj.css';
import '../../css/j/jna5_7bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wqf5v4byj"/><path class="jna5_7bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:conveyor-48-bold" {...props}></Icon>
