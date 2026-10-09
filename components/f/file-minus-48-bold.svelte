<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdos38jip.css';
import '../../css/z/z-21dwbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdos38jip"/><path class="z-21dwbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-minus-48-bold" {...props}></Icon>
