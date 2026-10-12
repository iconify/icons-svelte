<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozo7glmpq.css';
import '../../css/s/svf74obkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ozo7glmpq"/><path class="svf74obkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cat-48" {...props}></Icon>
