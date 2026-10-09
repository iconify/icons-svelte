<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdclrrbld.css';
import '../../css/z/zu1wjac1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kdclrrbld"/><path class="zu1wjac1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pier-48-bold" {...props}></Icon>
