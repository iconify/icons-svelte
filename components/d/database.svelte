<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo3-ksbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="oo3-ksbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:database" {...props}></Icon>
