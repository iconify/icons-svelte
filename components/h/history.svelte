<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvm4kcb4a.css';
import '../../css/f/fu2jxxb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tvm4kcb4a"/><path class="fu2jxxb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:history" {...props}></Icon>
