<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs6rvfdlb.css';
import '../../css/e/ea83p6byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs6rvfdlb"/><path class="ea83p6byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-pen-20" {...props}></Icon>
